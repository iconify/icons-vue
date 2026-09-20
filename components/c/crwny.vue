<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uas_n9iqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uas_n9iqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:crwny" /></template>
