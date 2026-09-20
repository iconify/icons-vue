<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/v/vl6c8ibxl.css';
import '../../css/r/ro5cgnb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="bc1fd0lxe"/><path class="vl6c8ibxl"/><path class="ro5cgnb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dashwise" /></template>
