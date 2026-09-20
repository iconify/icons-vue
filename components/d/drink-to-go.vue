<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4qj1eojy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4qj1eojy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:drink-to-go" /></template>
