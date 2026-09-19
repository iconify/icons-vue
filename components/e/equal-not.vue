<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjlsojv7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjlsojv7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:equal-not" /></template>
