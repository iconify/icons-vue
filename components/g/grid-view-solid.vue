<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqvx9ib_x.css';
import '../../css/p/p8he947hk.css';
import '../../css/k/kr2gl26lk.css';
import '../../css/j/jnn7fdc4o.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<rect class="clr-i-solid clr-i-solid-path-1 fqvx9ib_x"/><rect class="clr-i-solid clr-i-solid-path-2 p8he947hk"/><rect class="clr-i-solid clr-i-solid-path-3 kr2gl26lk"/><rect class="clr-i-solid clr-i-solid-path-4 jnn7fdc4o"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:grid-view-solid" /></template>
