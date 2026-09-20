<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a65wbby8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="a65wbby8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:fingerprint-scan" /></template>
