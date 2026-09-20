<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok8dtubfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok8dtubfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-download-alt" /></template>
