<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et2c2sm_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et2c2sm_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-transgender" /></template>
