<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sobe6ub7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sobe6ub7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gift-card-02" /></template>
