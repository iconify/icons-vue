<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3jdj3btd.css';
import '../../css/t/t61q91bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3jdj3btd"/><path class="t61q91bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cetus" /></template>
