<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sai67h5sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sai67h5sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbells-outline" /></template>
