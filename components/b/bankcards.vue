<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2ihnjbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="k2ihnjbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:bankcards" /></template>
