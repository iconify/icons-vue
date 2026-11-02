<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrttn8byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrttn8byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beef-off-fill" /></template>
