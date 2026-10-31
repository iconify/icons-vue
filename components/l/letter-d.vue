<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk3s6ubsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk3s6ubsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-d" /></template>
