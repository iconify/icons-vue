<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iobqwoh3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iobqwoh3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-up-down" /></template>
