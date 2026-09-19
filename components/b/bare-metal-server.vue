<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k43y_he5a.css';
import '../../css/u/uqvmiit-o.css';
import '../../css/y/y8mkib1ak.css';
import '../../css/r/rs7rz-b0d.css';
import '../../css/j/jzccu8bfu.css';
import '../../css/j/j1pak7bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="k43y_he5a"/><path class="uqvmiit-o"/><circle class="y8mkib1ak"/><path class="rs7rz-b0d"/><circle class="jzccu8bfu"/><path class="j1pak7bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bare-metal-server" /></template>
