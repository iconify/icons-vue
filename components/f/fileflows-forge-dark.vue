<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztw6jsdfu.css';
import '../../css/p/po93bzbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztw6jsdfu"/><path class="po93bzbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fileflows-forge-dark" /></template>
