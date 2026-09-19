<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/o51294bng.css';
import '../../css/s/sey112v-v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxuCMgbns"><g class="ufeehvblu"><path class="o51294bng"/><path class="sey112v-v"/></g></mask></defs><path mask="url(#SVGxuCMgbns)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:document-folder" /></template>
