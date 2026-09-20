<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf4fnjzzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf4fnjzzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ghost-3" /></template>
