<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kufnkgbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kufnkgbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:library-remove" /></template>
