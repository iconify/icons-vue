<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnme3-bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnme3-bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-androgyne" /></template>
