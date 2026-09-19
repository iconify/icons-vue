<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfcixgzhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfcixgzhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-team-02" /></template>
