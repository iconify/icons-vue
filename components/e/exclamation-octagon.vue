<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhhghx8wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhhghx8wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:exclamation-octagon" /></template>
