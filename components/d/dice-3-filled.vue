<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbgir05ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgir05ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dice-3-filled" /></template>
