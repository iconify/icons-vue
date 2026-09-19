<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j396_ylra.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged j396_ylra"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-1--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:hard-disk-solid-badged" /></template>
