<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of2kmjqzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of2kmjqzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:envelope-light" /></template>
