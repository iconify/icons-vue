<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubrgnsref.css';
import '../../css/x/xl-jarb6g.css';
import '../../css/p/p8b3qu2bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubrgnsref"/><path class="xl-jarb6g"/><path class="p8b3qu2bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-bold" /></template>
