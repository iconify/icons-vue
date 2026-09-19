<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8h2ct16o.css';
import '../../css/a/a624i4-jv.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<rect class="clr-i-solid clr-i-solid-path-1 k8h2ct16o" transform="rotate(90 18 18)"/><path class="a624i4-jv clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:credit-card-solid" /></template>
