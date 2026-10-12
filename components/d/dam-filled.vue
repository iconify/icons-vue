<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtkdzbbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtkdzbbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dam-filled" /></template>
