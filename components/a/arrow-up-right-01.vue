<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/civj-4e9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="civj-4e9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-right-01" /></template>
