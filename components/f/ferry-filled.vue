<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8v0pl8xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8v0pl8xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ferry-filled" /></template>
