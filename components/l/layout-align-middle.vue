<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgaxh98rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgaxh98rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-align-middle" /></template>
