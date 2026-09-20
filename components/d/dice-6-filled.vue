<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmsfnbbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmsfnbbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dice-6-filled" /></template>
