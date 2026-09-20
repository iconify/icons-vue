<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmtv_jb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmtv_jb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ironing-steam-filled" /></template>
