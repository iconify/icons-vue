<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_bki1las.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_bki1las"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cakephp-old" /></template>
