<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/s/so3crc7yr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdbVcbVMg"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="so3crc7yr"/></g></mask></defs><path mask="url(#SVGdbVcbVMg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:f-five-key" /></template>
