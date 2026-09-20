<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw50y7rwg.css';
import '../../css/e/ec0iwibgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw50y7rwg"/><path class="ec0iwibgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-trash-light" /></template>
