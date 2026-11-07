<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozgt7tt7d.css';
import '../../css/r/rhx5tab9t.css';
import '../../css/l/l49vyab9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozgt7tt7d"/><path class="rhx5tab9t"/><path clip-rule="evenodd" class="l49vyab9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:jar-of-pills-2-outline" /></template>
