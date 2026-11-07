<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq0eybcdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vq0eybcdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-id-solid" /></template>
