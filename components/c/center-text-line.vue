<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssuu4cckt.css';
import '../../css/b/bqa99--xe.css';
import '../../css/q/q7mk89i5h.css';
import '../../css/h/hmzkwwxtf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ssuu4cckt"/><path class="bqa99--xe clr-i-outline clr-i-outline-path-2"/><path class="clr-i-outline clr-i-outline-path-3 q7mk89i5h"/><path class="clr-i-outline clr-i-outline-path-4 hmzkwwxtf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:center-text-line" /></template>
