<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwfssbtso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwfssbtso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-attic" /></template>
