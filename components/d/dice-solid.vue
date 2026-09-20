<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk_pq0bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk_pq0bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dice-solid" /></template>
