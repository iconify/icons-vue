<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmunasb2f.css';
import '../../css/v/vg_16dn1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmunasb2f"/><path clip-rule="evenodd" class="vg_16dn1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-nine-duotone" /></template>
