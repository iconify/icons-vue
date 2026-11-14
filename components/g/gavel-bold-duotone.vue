<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="gwwza7bty"/><path class="pgnaf2bxi"/><path class="b-sju7p-r"/><path class="pe3-64zzy"/></g><path class="vdiewsb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gavel-bold-duotone" /></template>
<style>
.b-sju7p-r {
  d: path("M9.96289 11.7119L9.46875 12.207C8.73565 12.94 8.36865 13.3066 7.91309 13.3066C7.45753 13.3066 7.09066 12.9403 6.35742 12.207L5.36719 11.2168C4.6343 10.4839 4.26758 10.1165 4.26758 9.66113C4.26769 9.20577 4.63375 8.83911 5.36621 8.10645L5.86133 7.61035L9.96289 11.7119Z");
}

.gwwza7bty {
  d: path("M12.2891 20.9111C12.7033 20.9111 13.0391 21.2469 13.0391 21.6611C13.0389 22.0752 12.7032 22.4111 12.2891 22.4111H3.28906C2.87497 22.4111 2.53926 22.0752 2.53906 21.6611C2.53906 21.2469 2.87485 20.9111 3.28906 20.9111H12.2891Z");
}

.pe3-64zzy {
  d: path("M11.5898 2.33887C12.0453 2.33887 12.4126 2.7048 13.1455 3.4375L14.1357 4.42871C14.869 5.16191 15.2354 5.52877 15.2354 5.98438C15.2353 6.43951 14.8696 6.80576 14.1377 7.53809L13.6406 8.03516L9.53906 3.93359L10.0352 3.4375C10.7678 2.70508 11.1344 2.33905 11.5898 2.33887Z");
}

.pgnaf2bxi {
  d: path("M21.2402 18.252C21.533 18.5448 21.5329 19.0196 21.2402 19.3125C20.9474 19.6053 20.4726 19.6053 20.1797 19.3125L11.2715 10.4043L12.332 9.34375L21.2402 18.252Z");
}

.vdiewsb9h {
  fill: currentColor;
  d: path("M13.6396 8.03418L9.96289 11.7119L5.86133 7.61035L9.53809 3.93262L13.6396 8.03418Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
