<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw14v029a.css';
import '../../css/r/r3-2ecc9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw14v029a"/><path class="r3-2ecc9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:database-alt-filled" /></template>
