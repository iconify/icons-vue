<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlnuinbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="qlnuinbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:close-up-mode" /></template>
