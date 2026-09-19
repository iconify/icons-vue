<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d05zlbb9a.css';
import '../../css/r/rx-9rn84i.css';
import '../../css/u/uvi4e24wd.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 d05zlbb9a"/><circle class="clr-i-outline clr-i-outline-path-2 rx-9rn84i"/><path class="clr-i-outline clr-i-outline-path-3 uvi4e24wd"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:exclamation-triangle-line" /></template>
