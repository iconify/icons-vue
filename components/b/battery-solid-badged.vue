<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmf0ecbhq.css';
import '../../css/t/t_3i6ebpc.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-1--badged lmf0ecbhq"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged t_3i6ebpc"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:battery-solid-badged" /></template>
