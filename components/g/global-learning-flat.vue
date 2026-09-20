<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/do_u7wljd.css';
import '../../css/f/f50bkxkxz.css';
import '../../css/f/frprfzvzu.css';
import '../../css/l/lld3lbcdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="do_u7wljd"/><path class="f50bkxkxz"/><path class="frprfzvzu"/><path class="lld3lbcdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:global-learning-flat" /></template>
