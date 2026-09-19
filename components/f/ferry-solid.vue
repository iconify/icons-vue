<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilg24imlf.css';
import '../../css/i/i6-74zq0i.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 ilg24imlf"/><path class="clr-i-solid clr-i-solid-path-2 i6-74zq0i"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:ferry-solid" /></template>
