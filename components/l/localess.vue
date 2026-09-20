<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncgeo_vzx.css';
import '../../css/g/glg0knb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ncgeo_vzx"/><path class="glg0knb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:localess" /></template>
