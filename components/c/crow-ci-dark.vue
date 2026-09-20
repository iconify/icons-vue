<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7yjv0aal.css';
import '../../css/g/g--_bbc2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7yjv0aal"/><path class="g--_bbc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crow-ci-dark" /></template>
