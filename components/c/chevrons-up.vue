<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv-0_9b5j.css';
import '../../css/t/t141ssbgj.css';
import '../../css/x/xgz4a685r.css';
import '../../css/u/umxz_5b4r.css';
import '../../css/k/kehzw2byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv-0_9b5j wm-shadow"/><path class="t141ssbgj wm-k"/><path class="wm-k xgz4a685r"/><path class="umxz_5b4r wm-a"/><path class="kehzw2byj wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:chevrons-up" /></template>
