<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sois_5fph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sois_5fph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:database-backup" /></template>
