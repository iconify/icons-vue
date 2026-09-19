<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/k8vms3b0m.css';
import '../../css/b/b5xb-mgxl.css';
import '../../css/u/u7wt_xx-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k8vms3b0m"/><path class="b5xb-mgxl"/><path class="u7wt_xx-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:external-drive" /></template>
