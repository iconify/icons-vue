<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq9qmabfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq9qmabfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:carry-on-luggage" /></template>
