<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0f5lqbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0f5lqbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cancel-02" /></template>
