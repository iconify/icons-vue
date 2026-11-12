<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h21hmgjli"/><path class="j2mhdfb5v"/><g class="xtpeb-edw"><path class="de5deccyd"/><path class="tqknh7bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fog-bold-duotone" /></template>
<style>
.de5deccyd {
  d: path("M19 18.25C19.4142 18.25 19.75 18.5858 19.75 19C19.75 19.4142 19.4142 19.75 19 19.75H5C4.58579 19.75 4.25 19.4142 4.25 19C4.25 18.5858 4.58579 18.25 5 18.25H19Z");
}

.h21hmgjli {
  fill: currentColor;
  d: path("M16 21.25C16.4142 21.25 16.75 21.5858 16.75 22C16.75 22.4142 16.4142 22.75 16 22.75H8C7.58579 22.75 7.25 22.4142 7.25 22C7.25 21.5858 7.58579 21.25 8 21.25H16Z");
}

.j2mhdfb5v {
  fill: currentColor;
  d: path("M22 15.249C22.4142 15.249 22.75 15.5848 22.75 15.999C22.75 16.4132 22.4142 16.749 22 16.749H2C1.58579 16.749 1.25 16.4132 1.25 15.999C1.25013 15.5849 1.58586 15.249 2 15.249H22Z");
}

.tqknh7bma {
  d: path("M12.4766 2C15.416 2.00019 17.8372 4.19365 18.1553 7.01465C20.393 7.77989 21.9998 9.88092 22 12.3525C22 13.4116 21.7047 14.403 21.1914 15.25H2.27051C2.09538 14.7879 2 14.2872 2 13.7646C2.00003 11.4256 3.91922 9.5293 6.28613 9.5293C6.57009 9.52932 6.84769 9.5563 7.11621 9.6084C6.88725 8.99756 6.76177 8.33698 6.76172 7.64746C6.76172 4.52868 9.32065 2 12.4766 2Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
