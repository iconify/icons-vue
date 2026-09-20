<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyhh4ob9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyhh4ob9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:inner-shadow-top-filled" /></template>
