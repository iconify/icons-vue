<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzd_sebbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzd_sebbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fivem" /></template>
