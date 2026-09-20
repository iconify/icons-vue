<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0m72u3lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0m72u3lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alphabet-runes" /></template>
