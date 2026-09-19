<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/eas391big.css';
import '../../css/y/y9pme5b7n.css';
import '../../css/g/gtv82xhfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eas391big"/><path class="y9pme5b7n"/><path class="gtv82xhfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:fireworks" /></template>
