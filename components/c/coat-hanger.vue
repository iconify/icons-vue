<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/sz9e8238f.css';
import '../../css/k/kxnbaldms.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoDnRsbqV"><g class="aql7dnt-u"><path class="sz9e8238f"/><path class="kxnbaldms"/></g></mask></defs><path mask="url(#SVGoDnRsbqV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:coat-hanger" /></template>
