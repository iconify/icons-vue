<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztw00-h6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ztw00-h6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:first-aid-kit-solid" /></template>
