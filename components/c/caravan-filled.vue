<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snid97b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snid97b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:caravan-filled" /></template>
