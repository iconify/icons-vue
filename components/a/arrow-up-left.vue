<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xendcgwaw.css';
import '../../css/x/xg4x14bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xendcgwaw"/><path class="xg4x14bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:arrow-up-left" /></template>
