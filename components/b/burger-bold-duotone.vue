<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="yryvs195z"/><path class="tkxwf5bvw"/></g><path class="zwryysb6t"/><path class="tni2csbjj"/><path class="fz048-bql"/><path class="rdltc9btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:burger-bold-duotone" /></template>
<style>
.fz048-bql {
  fill: currentColor;
  d: path("M9 8.50037C9.4142 8.50037 9.75 8.83617 9.75 9.25037C9.7498 9.6644 9.41408 10.0004 9 10.0004C8.58592 10.0004 8.2502 9.6644 8.25 9.25037C8.25 8.83617 8.5858 8.50037 9 8.50037Z");
}

.rdltc9btv {
  fill: currentColor;
  d: path("M12 7.59998C12.4142 7.59998 12.75 7.93578 12.75 8.34998C12.75 8.76418 12.4142 9.09998 12 9.09998C11.5858 9.09998 11.25 8.76418 11.25 8.34998C11.25 7.93578 11.5858 7.59998 12 7.59998Z");
}

.tkxwf5bvw {
  d: path("M12 5.95001C16.8 5.95001 20 8.05021 20 11.6502H4C4 8.05021 7.2 5.95001 12 5.95001Z");
}

.tni2csbjj {
  fill: currentColor;
  d: path("M15 8.59998C15.4142 8.59998 15.75 8.93578 15.75 9.34998C15.75 9.76418 15.4142 10.1 15 10.1C14.5858 10.1 14.25 9.76418 14.25 9.34998C14.25 8.93578 14.5858 8.59998 15 8.59998Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yryvs195z {
  d: path("M20 14.8504V16.0496C20 17.3496 18.8001 18.0496 16.7002 18.0496H7.2998C5.19993 18.0496 4 17.3496 4 16.0496V14.8504H20Z");
}

.zwryysb6t {
  fill: currentColor;
  d: path("M19.6006 11.6498C20.4843 11.6498 21.2012 12.3667 21.2012 13.2504C21.201 14.1339 20.4842 14.85 19.6006 14.85H4.40039C3.51698 14.8498 2.80097 14.1338 2.80078 13.2504C2.80078 12.3668 3.51687 11.65 4.40039 11.6498H19.6006Z");
}

</style>
