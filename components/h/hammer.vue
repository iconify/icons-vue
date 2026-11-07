<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrw163bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrw163bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:hammer" /></template>
