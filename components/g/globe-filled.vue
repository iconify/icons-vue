<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r-3e29blm.css';
import '../../css/y/yirn1hcot.css';
import '../../css/k/k8fun-b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="r-3e29blm"/><path class="yirn1hcot"/><path class="k8fun-b6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:globe-filled" /></template>
