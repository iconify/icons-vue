<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we9ae-bgu.css';
import '../../css/u/uq29kf5fe.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged we9ae-bgu"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged uq29kf5fe"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-3--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:display-solid-badged" /></template>
