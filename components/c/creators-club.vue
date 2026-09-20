<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6c56ebta.css';
import '../../css/u/ulpze-4na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6c56ebta"/><path class="ulpze-4na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:creators-club" /></template>
