<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi4rgpbsh.css';
import '../../css/i/ih3xvpyom.css';
import '../../css/j/jxgdkxb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hi4rgpbsh"/><path class="ih3xvpyom"/><path class="jxgdkxb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:color-palette-line" /></template>
