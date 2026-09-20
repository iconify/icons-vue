<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqzky_tya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqzky_tya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dashlane" /></template>
