<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":263};
const content = `<defs><linearGradient id="SVGCSkvIlYg" x1="74.353%" x2="29.277%" y1="2.347%" y2="88.929%"><stop offset=".141%" class="g3lww2juo"/><stop offset="100%" class="z8ltkhkkn"/></linearGradient><linearGradient id="SVGAwjIvexH" x1="30.44%" x2="52.276%" y1="82.16%" y2="25.933%"><stop offset=".141%" class="g3lww2juo"/><stop offset="100%" class="z8ltkhkkn"/></linearGradient><linearGradient id="SVGvpMgTcNm" x1="88.725%" x2="49.236%" y1="104.492%" y2="33.37%"><stop offset=".01%" class="g3lww2juo"/><stop offset="100%" class="z8ltkhkkn"/></linearGradient><linearGradient id="SVGnbSMIUfN" x1="128.919%" x2="37.716%" y1="-49.459%" y2="62.988%"><stop offset=".01%" class="g3lww2juo"/><stop offset="100%" class="oj1cvxdco"/></linearGradient><linearGradient id="SVGgk4oAdHy" x1="90.849%" x2="2.749%" y1="67.285%" y2="33.603%"><stop offset="0%" class="z8ltkhkkn"/><stop offset="99.99%" class="e_pe6c12s"/></linearGradient><linearGradient id="SVGGQfqjbAh" x1="26.288%" x2="50.264%" y1="-17.539%" y2="49.711%"><stop offset="0%" class="z8ltkhkkn"/><stop offset="99.99%" class="z5u46vgbz"/></linearGradient><linearGradient id="SVGgc5N9d9r" x1="124.516%" x2="32.767%" y1="95.746%" y2="39.443%"><stop offset="0%" class="vc--wpv5i"/><stop offset="99.99%" class="e_pe6c12s"/></linearGradient><linearGradient id="SVGfH5hiZnn" x1="27.461%" x2="72.142%" y1="13.176%" y2="75.008%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGF5cKDcel" x1="38.7%" x2="61.839%" y1="29.949%" y2="79.7%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGFQBSycHu" x1="19.099%" x2="63.507%" y1="47.308%" y2="52.344%"><stop offset=".141%" class="g3lww2juo"/><stop offset="73.8%" class="oj1cvxdco"/></linearGradient><linearGradient id="SVG5cOLMbhV" x1="65.335%" x2="40.463%" y1="-25.609%" y2="63.968%"><stop offset=".141%" class="vc--wpv5i"/><stop offset="73.8%" class="oj1cvxdco"/></linearGradient><linearGradient id="SVGANHrrkAF" x1="20.968%" x2="95.392%" y1="-11.809%" y2="101.563%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="vc--wpv5i"/></linearGradient></defs><path fill="url(#SVGCSkvIlYg)" class="n3wauccyl"/><path fill="url(#SVGAwjIvexH)" class="mcgbrlgje"/><path fill="url(#SVGvpMgTcNm)" class="rqs460g0z"/><path fill="url(#SVGnbSMIUfN)" class="rqs460g0z"/><path fill="url(#SVGgk4oAdHy)" class="veooji9gb"/><path fill="url(#SVGGQfqjbAh)" class="veooji9gb"/><path fill="url(#SVGgc5N9d9r)" class="veooji9gb"/><path fill="url(#SVGfH5hiZnn)" transform="translate(50.449 69.794)" class="o360kcbir"/><path fill="url(#SVGF5cKDcel)" transform="translate(126.124 48.026)" class="zn197mbri"/><path fill="url(#SVGFQBSycHu)" class="mcgbrlgje"/><path fill="url(#SVG5cOLMbhV)" class="mcgbrlgje"/><path fill="url(#SVGANHrrkAF)" transform="translate(99.935 10.092)" class="s780rg02j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:activeloop-icon" /></template>
<style>
.e_pe6c12s {
  stop-color: var(--svg-color--f9b239, #f9b239);
  stop-opacity: 0;
}

.g3lww2juo {
  stop-color: var(--svg-color--ed7546, #ed7546);
}

.mcgbrlgje {
  d: path("M223.603 120.044c-3.638 9.457-8.002 18.914-14.55 28.37c-7.274 10.185-15.276 18.914-24.005 25.462c-16.005 12.366-33.463 20.368-51.65 22.55c21.096-11.639 38.555-31.28 47.285-56.74c5.092-14.55 7.274-29.827 6.547-43.648c0-5.82-.728-12.367-2.182-18.187c-4.365-20.368-16.005-39.282-34.19-51.649c-2.183-2.182-5.093-4.365-8.003-5.82c0 0-.727 0-.727-.727c-11.64-5.82-25.461-8.73-41.465-8.002c3.637-1.455 12.366-5.092 16.731-6.547c25.461-8.73 56.014-6.547 77.838 8.73c12.367 8.729 21.824 20.368 27.643 33.462c8.73 21.824 8.73 48.012.728 72.746");
}

.n3wauccyl {
  d: path("M198.142 240.802c-58.924 39.282-138.217 22.55-176.772-36.373c-29.098-43.648-27.643-98.207-.728-139.672c9.457-14.549 21.824-27.643 37.1-37.828c8.73-5.82 29.099-16.731 49.468-16.004c15.276.728 31.28 5.093 44.375 14.55c18.186 12.366 29.825 31.28 34.19 51.649c1.455 6.547 2.182 13.822 2.182 20.369c-8.73-10.912-21.823-18.914-36.372-23.279c-6.548-2.182-13.822-2.91-21.824-3.637c-40.738-1.455-74.2 25.46-75.656 60.379c-.727 28.37 19.642 52.377 49.467 61.106c2.183.727 4.365 1.455 7.275 1.455l15.277 2.182c20.368-.727 41.465-8.73 58.924-22.55c8.729-7.275 16.731-15.277 24.006-25.462c6.547-8.73 10.911-18.914 14.549-28.37c8.73-24.734 8.002-50.923-.728-72.019c4.365 5.092 8.73 10.185 12.367 16.004c38.555 58.924 21.824 138.217-37.1 177.5");
}

.o360kcbir {
  d: path("M136.781 27.698c-8.73-10.912-24.006-20.369-37.1-24.006C92.406 1.51 85.131.055 77.857.055C35.665-1.4.747 26.243.02 61.889c-.728 29.098 18.913 51.649 49.467 60.379c2.182.727 11.639 2.91 11.639 2.91c-2.183-.728-4.365-1.456-7.275-1.456C24.026 114.993 3.657 90.26 4.384 62.616C5.84 27.698 39.302.782 80.04 2.237c7.274 0 14.549 1.455 21.823 3.638c12.367 2.91 26.916 11.639 34.918 21.823");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.oj1cvxdco {
  stop-color: var(--svg-color--ff6d35, #ff6d35);
  stop-opacity: 0;
}

.rqs460g0z {
  d: path("M111.574 94.583c-29.098 29.098-34.917 71.29-13.094 96.752c-26.916-10.185-45.102-33.463-43.647-59.652c1.455-34.918 34.918-61.834 75.655-60.379c5.093 0 9.457.728 14.55 1.455c-12.367 5.092-23.28 11.64-33.464 21.824");
}

.s780rg02j {
  d: path("M12.367.106C26.916-.62 39.283 2.29 53.104 11.746C71.291 24.84 82.93 46.664 87.294 67.76c1.456 9.457.728 21.096.728 21.096c0-7.275-.727-13.822-2.182-20.369c-4.365-20.369-16.004-39.282-34.19-51.65C37.827 7.382 22.55 3.018 7.274 2.29H0C0 1.56 10.184.106 12.367.106");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.veooji9gb {
  d: path("M198.142 240.802c-58.924 39.282-138.217 22.55-176.772-36.373c-29.098-43.648-27.643-98.207-.728-139.672c9.457-14.549 21.824-27.643 37.1-37.828c8.73-5.092 29.826-16.004 49.468-15.276c15.276.727 31.28 5.092 44.375 14.549c18.186 12.367 29.825 31.28 34.19 51.65c1.455 6.546 2.182 13.821 2.182 20.368c-8.73-10.912-23.278-19.641-36.372-23.278c-6.548-2.183-13.822-2.91-21.824-3.638c-40.738-1.455-74.2 25.461-75.656 60.38c-.727 28.37 19.642 52.376 49.467 61.105c2.183.728 4.365 1.455 7.275 1.455l15.277 2.183c20.368-.728 41.465-8.73 58.924-22.551c8.729-7.275 16.731-15.277 24.006-25.461c6.547-8.73 10.911-18.914 14.549-28.371c8.73-24.734 8.002-50.922-.728-72.018c4.365 5.092 8.73 10.184 12.367 16.004c38.555 58.196 21.824 137.489-37.1 176.772");
}

.z5u46vgbz {
  stop-color: var(--svg-color--ed7546, #ed7546);
  stop-opacity: 0;
}

.z8ltkhkkn {
  stop-color: var(--svg-color--f9b239, #f9b239);
}

.zn197mbri {
  d: path("M59.651 130.942c8.73-6.547 17.46-14.549 24.734-24.733c6.547-8.73 10.912-18.914 14.549-28.371c8.002-24.734 8.002-53.104-.727-74.2L96.752 0c9.457 21.096 9.457 47.285.727 72.018c-3.637 9.457-8.002 18.914-14.549 28.37c-7.275 10.185-15.277 18.915-24.006 25.462C41.465 139.672 20.369 147.674 0 148.4c0 .727 29.826 4.365 59.651-17.459");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
