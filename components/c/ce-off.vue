<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhufzd_ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhufzd_ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ce-off" /></template>
