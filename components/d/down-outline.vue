<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2t_7jw2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g2t_7jw2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:down-outline" /></template>
