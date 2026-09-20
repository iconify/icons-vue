<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssc1-xone.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssc1-xone"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:id-filled" /></template>
