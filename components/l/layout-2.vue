<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4kfhgn3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4kfhgn3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-2" /></template>
