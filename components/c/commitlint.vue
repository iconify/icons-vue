<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgfakv3lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgfakv3lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:commitlint" /></template>
