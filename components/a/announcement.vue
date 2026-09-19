<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jiqs0bwjn.css';
import '../../css/t/tnva8r8up.css';
import '../../css/i/ic972l8rf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbrrVVdvZ"><g class="ufeehvblu"><rect class="jiqs0bwjn"/><path class="tnva8r8up"/><path class="ic972l8rf"/></g></mask></defs><path mask="url(#SVGbrrVVdvZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:announcement" /></template>
