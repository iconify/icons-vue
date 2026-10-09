<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-kpumbeo.css';
import '../../css/j/j98ub3buk.css';
import '../../css/k/kgoatob5h.css';
import '../../css/t/txtl48bjd.css';
import '../../css/w/w-e6kfbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j-kpumbeo"/><path class="j98ub3buk"/><path class="kgoatob5h"/><path class="txtl48bjd"/><path class="w-e6kfbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:island-48" /></template>
