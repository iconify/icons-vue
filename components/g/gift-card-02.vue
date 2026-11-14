<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpik002ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpik002ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gift-card-02" /></template>
