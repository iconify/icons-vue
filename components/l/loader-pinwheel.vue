<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/plv6wabjd.css';
import '../../css/d/d_vxw9yeb.css';
import '../../css/h/hvm4n6b8w.css';
import '../../css/s/shu3xdl9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="plv6wabjd"/><path class="d_vxw9yeb"/><path class="hvm4n6b8w"/><circle class="shu3xdl9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:loader-pinwheel" /></template>
