<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9mno1zme.css';
import '../../css/x/xh51xx53o.css';
import '../../css/e/eajk65b4i.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged d9mno1zme"/><circle class="clr-i-outline--badged clr-i-outline-path-2--badged xh51xx53o"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged eajk65b4i"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:help-outline-badged" /></template>
