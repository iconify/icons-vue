<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbk12mtzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="bbk12mtzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:file-f" /></template>
