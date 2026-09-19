<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw_globds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw_globds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:kidneys-outline-24px" /></template>
