<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz7sqrpkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iz7sqrpkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-sm-20" /></template>
