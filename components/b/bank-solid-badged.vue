<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1s00oj4b.css';
import '../../css/k/khykwcccx.css';
import '../../css/i/i72yceb1j.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged v1s00oj4b"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged khykwcccx"/><path class="clr-i-solid--badged clr-i-solid-path-3--badged i72yceb1j"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bank-solid-badged" /></template>
