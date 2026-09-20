<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9k3s_lst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9k3s_lst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-redo-alt" /></template>
