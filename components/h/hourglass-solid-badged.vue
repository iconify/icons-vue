<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1c9mbcsk.css';
import '../../css/o/oipwkwbqf.css';
import '../../css/s/s1z7lvb-e.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged s1c9mbcsk"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged oipwkwbqf"/><path class="clr-i-solid--badged clr-i-solid-path-3--badged s1z7lvb-e"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:hourglass-solid-badged" /></template>
