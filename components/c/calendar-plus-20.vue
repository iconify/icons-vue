<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-bc1ybft.css';
import '../../css/a/a99zzxb0t.css';
import '../../css/f/fp91mvbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f-bc1ybft"/><path class="a99zzxb0t"/><path class="fp91mvbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-plus-20" /></template>
