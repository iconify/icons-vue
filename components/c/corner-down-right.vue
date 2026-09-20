<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyyvzf4ru.css';
import '../../css/v/vlxt_3bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyyvzf4ru"/><path class="vlxt_3bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:corner-down-right" /></template>
