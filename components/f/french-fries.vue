<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/p/pb418gb3z.css';
import '../../css/q/q-c3nrjwl.css';
import '../../css/k/k7vaebzuk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUrLoXbLe"><g class="s9cl3zbei"><path class="pb418gb3z"/><path class="q-c3nrjwl"/><ellipse class="k7vaebzuk"/></g></mask></defs><path mask="url(#SVGUrLoXbLe)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:french-fries" /></template>
