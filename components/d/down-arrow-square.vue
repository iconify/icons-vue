<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq5ltcb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq5ltcb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:down-arrow-square" /></template>
