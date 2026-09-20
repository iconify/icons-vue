<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr2tweb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="zr2tweb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:businesscontact" /></template>
