<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/iavqdjdgi.css';
import '../../css/n/npiz6qlvn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGblMKScBJ"><g class="aql7dnt-u"><path clip-rule="evenodd" class="iavqdjdgi"/><path class="npiz6qlvn"/></g></mask></defs><path mask="url(#SVGblMKScBJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hanger" /></template>
