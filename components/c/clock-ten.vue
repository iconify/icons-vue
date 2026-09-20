<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tswetb8fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tswetb8fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:clock-ten" /></template>
