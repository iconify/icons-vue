<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijupqacst.css';
import '../../css/w/waapkib7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijupqacst"/><path class="waapkib7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-stroke-circle-half" /></template>
