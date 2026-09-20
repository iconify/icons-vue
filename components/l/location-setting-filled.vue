<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqze8hb0i.css';
import '../../css/x/xsi-ndbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqze8hb0i"/><path class="xsi-ndbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:location-setting-filled" /></template>
