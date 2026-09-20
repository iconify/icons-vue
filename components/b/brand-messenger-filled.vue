<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va8ywzbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va8ywzbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-messenger-filled" /></template>
