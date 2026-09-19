<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdvrqq5on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdvrqq5on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-basketball-outline" /></template>
