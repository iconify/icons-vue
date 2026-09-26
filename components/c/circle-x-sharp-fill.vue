<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q19gspbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-x-sharp-fill" /></template>
<style>
.q19gspbyn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM14.8443 7.6002L12 10.4445L9.1556 7.6003L7.6002 9.1557L10.4445 12L7.6003 14.8444L9.1557 16.3998L12 13.5555L14.8444 16.3997L16.3998 14.8443L13.5555 12L16.3997 9.1556L14.8443 7.6002Z");
}

</style>
