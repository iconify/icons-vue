<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmunasb2f.css';
import '../../css/w/w_bhenb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmunasb2f"/><path class="w_bhenb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-duotone" /></template>
