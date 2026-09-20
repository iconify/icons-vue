<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_2biibtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_2biibtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-minus-alt" /></template>
