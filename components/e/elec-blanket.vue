<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj_ri-b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_ri-b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:elec-blanket" /></template>
