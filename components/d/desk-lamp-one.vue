<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/noua3z6jc.css';
import '../../css/t/tqncmkbeo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5t3VEzWz"><g class="v3_i3wktz"><path class="noua3z6jc"/><path class="tqncmkbeo"/></g></mask></defs><path mask="url(#SVG5t3VEzWz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:desk-lamp-one" /></template>
